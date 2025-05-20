# Function: <code>devm_of_platform_populate</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:100
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:107
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:116
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:122
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:122
Inline: True
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
int devm_of_platform_populate(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffff800010b6df78)
Location: drivers/of/platform.c:599
Inline: False
Direct callers:
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_probe
  - drivers/clk/mediatek/clk-mt7622-aud.c:clk_mt7622_audiosys_init
  - drivers/clk/mediatek/clk-mt8183-audio.c:clk_mt8183_audio_probe
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
```
**Symbols:**

```
ffff800010b6df78-ffff800010b6e024: devm_of_platform_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devm_of_platform_populate(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c0c50df0)
Location: drivers/of/platform.c:599
Inline: False
Direct callers:
  - drivers/clk/mediatek/clk-mt7622-aud.c:clk_mt7622_audiosys_init
  - drivers/soc/samsung/exynos-pmu.c:exynos_pmu_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
```
**Symbols:**

```
c0c50df0-c0c50e80: devm_of_platform_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devm_of_platform_populate(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c000000000c487b0)
Location: drivers/of/platform.c:599
Inline: False
Direct callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
**Symbols:**

```
c000000000c487b0-c000000000c488a8: devm_of_platform_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devm_of_platform_populate(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffffffe000722922)
Location: drivers/of/platform.c:599
Inline: False
Direct callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
**Symbols:**

```
ffffffe000722922-ffffffe0007229b4: devm_of_platform_populate (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:102
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
