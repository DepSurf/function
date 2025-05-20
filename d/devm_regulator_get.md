# Function: <code>devm_regulator_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff814de950)
Location: drivers/regulator/devres.c:75
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
```
**Symbols:**

```
ffffffff814de950-ffffffff814de962: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8152fae0)
Location: drivers/regulator/devres.c:75
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff8152fae0-ffffffff8152faf2: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8155c4a7)
Location: drivers/regulator/devres.c:75
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff8155c140-ffffffff8155c152: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81570bc0)
Location: drivers/regulator/devres.c:56
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff81570bc0-ffffffff81570bd2: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff815d4e60)
Location: drivers/regulator/devres.c:56
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff815d4e60-ffffffff815d4e72: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8160dc60)
Location: drivers/regulator/devres.c:56
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff8160dc60-ffffffff8160dc72: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8162a780)
Location: drivers/regulator/devres.c:56
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff8162a780-ffffffff8162a792: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8165e340)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff8165e340-ffffffff8165e352: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81680ab0)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff81680ab0-ffffffff81680ac2: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81731c30)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff81731c30-ffffffff81731c42: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8174dd50)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff8174dd50-ffffffff8174dd62: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff817318d0)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff817318d0-ffffffff817318e2: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff817b1980)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff817b1980-ffffffff817b1992: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff818ed110)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff818ed110-ffffffff818ed12c: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a445d0)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff81a445d0-ffffffff81a445ec: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a8e780)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff81a8e780-ffffffff81a8e79c: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81ae0ff0)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff81ae0ff0-ffffffff81ae100c: devm_regulator_get (STB_GLOBAL)
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
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffff80001084a6e0)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
```
**Symbols:**

```
ffff80001084a6e0-ffff80001084a718: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (c0953d0c)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-tegra124-dfll-fcpu.c:tegra124_dfll_fcpu_probe
  - drivers/soc/imx/gpc.c:imx_gpc_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked
```
**Symbols:**

```
c0953d0c-c0953d2c: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (c0000000008e7ef0)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
c0000000008e7ef0-c0000000008e7f08: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffe00052a3de)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffe00052a3de-ffffffe00052a412: devm_regulator_get (STB_GLOBAL)
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
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81646530)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81646530-ffffffff81646542: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81626990)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81626990-ffffffff816269a2: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff816748f0)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff816748f0-ffffffff81674902: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct regulator *devm_regulator_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8168ef50)
Location: drivers/regulator/devres.c:51
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff8168ef50-ffffffff8168ef62: devm_regulator_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
