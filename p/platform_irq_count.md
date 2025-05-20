# Function: <code>platform_irq_count</code>

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
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8159f6b0)
Location: drivers/base/platform.c:126
Inline: False
```
**Symbols:**

```
ffffffff8159f6b0-ffffffff8159f6e8: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815cdcf0)
Location: drivers/base/platform.c:141
Inline: False
```
**Symbols:**

```
ffffffff815cdcf0-ffffffff815cdd28: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e2720)
Location: drivers/base/platform.c:141
Inline: False
```
**Symbols:**

```
ffffffff815e2720-ffffffff815e2758: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816498d0)
Location: drivers/base/platform.c:141
Inline: False
```
**Symbols:**

```
ffffffff816498d0-ffffffff81649908: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81684e90)
Location: drivers/base/platform.c:140
Inline: False
```
**Symbols:**

```
ffffffff81684e90-ffffffff81684ec8: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a4ae0)
Location: drivers/base/platform.c:141
Inline: False
```
**Symbols:**

```
ffffffff816a4ae0-ffffffff816a4b18: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816ddab0)
Location: drivers/base/platform.c:179
Inline: False
```
**Symbols:**

```
ffffffff816ddab0-ffffffff816ddaed: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81701bb0)
Location: drivers/base/platform.c:206
Inline: False
```
**Symbols:**

```
ffffffff81701bb0-ffffffff81701bed: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bc9b0)
Location: drivers/base/platform.c:264
Inline: False
```
**Symbols:**

```
ffffffff817bc9b0-ffffffff817bc9ed: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d18b0)
Location: drivers/base/platform.c:295
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff817d18b0-ffffffff817d18ed: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b52e0)
Location: drivers/base/platform.c:294
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff817b52e0-ffffffff817b531d: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183e5d0)
Location: drivers/base/platform.c:274
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff8183e5d0-ffffffff8183e60d: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81981410)
Location: drivers/base/platform.c:278
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff81981410-ffffffff81981450: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aeef70)
Location: drivers/base/platform.c:278
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff81aeef70-ffffffff81aeefb0: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3d458)
Location: drivers/base/platform.c:278
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff81b3d360-ffffffff81b3d3a0: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b94f98)
Location: drivers/base/platform.c:279
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff81b94ea0-ffffffff81b94ee0: platform_irq_count (STB_GLOBAL)
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
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108eddd0)
Location: drivers/base/platform.c:206
Inline: False
Direct callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/perf/arm_pmu_platform.c:pmu_parse_irqs
```
**Symbols:**

```
ffff8000108eddd0-ffff8000108ede1c: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09dbc58)
Location: drivers/base/platform.c:206
Inline: False
Direct callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_setup
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
```
**Symbols:**

```
c09dbc58-c09dbca4: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000986330)
Location: drivers/base/platform.c:206
Inline: False
```
**Symbols:**

```
c000000000986330-c0000000009863a8: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe000580f40)
Location: drivers/base/platform.c:206
Inline: False
```
**Symbols:**

```
ffffffe000580f40-ffffffe000580f8a: platform_irq_count (STB_GLOBAL)
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
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c7300)
Location: drivers/base/platform.c:206
Inline: False
```
**Symbols:**

```
ffffffff816c7300-ffffffff816c733d: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a2600)
Location: drivers/base/platform.c:206
Inline: False
```
**Symbols:**

```
ffffffff816a2600-ffffffff816a263d: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f5870)
Location: drivers/base/platform.c:206
Inline: False
```
**Symbols:**

```
ffffffff816f5870-ffffffff816f58ad: platform_irq_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int platform_irq_count(struct platform_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81710100)
Location: drivers/base/platform.c:206
Inline: False
```
**Symbols:**

```
ffffffff81710100-ffffffff8171013d: platform_irq_count (STB_GLOBAL)
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
