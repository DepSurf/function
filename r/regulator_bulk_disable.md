# Function: <code>regulator_bulk_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814daa80)
Location: drivers/regulator/core.c:3546
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff814daa80-ffffffff814dab1a: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152c6a0)
Location: drivers/regulator/core.c:3580
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff8152c6a0-ffffffff8152c73b: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81558d00)
Location: drivers/regulator/core.c:3644
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff81558d00-ffffffff81558d97: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156d650)
Location: drivers/regulator/core.c:3667
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff8156d650-ffffffff8156d70f: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d1a50)
Location: drivers/regulator/core.c:3675
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff815d1a50-ffffffff815d1b0f: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3849
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff8160cb44-ffffffff8160cb96: regulator_bulk_disable.cold.60 (STB_LOCAL)
ffffffff81609b80-ffffffff81609bdc: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4471
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff81629370-ffffffff816293c2: regulator_bulk_disable.cold.70 (STB_LOCAL)
ffffffff816273f0-ffffffff8162744c: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4496
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff8165d104-ffffffff8165d152: regulator_bulk_disable.cold (STB_LOCAL)
ffffffff8165ae50-ffffffff8165aeab: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4506
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff8167f947-ffffffff8167f995: regulator_bulk_disable.cold (STB_LOCAL)
ffffffff8167e5a0-ffffffff8167e5fb: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4555
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff81730940-ffffffff81730992: regulator_bulk_disable.cold (STB_LOCAL)
ffffffff8172ee50-ffffffff8172eef7: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4693
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81c06ea4-ffffffff81c06ef5: regulator_bulk_disable.cold (STB_LOCAL)
ffffffff8174bac0-ffffffff8174bb6a: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4695
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81bf8b3f-ffffffff81bf8b90: regulator_bulk_disable.cold (STB_LOCAL)
ffffffff8172f1e0-ffffffff8172f28a: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4832
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81cf7d6d-ffffffff81cf7dbe: regulator_bulk_disable.cold (STB_LOCAL)
ffffffff817aeea0-ffffffff817aef4a: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4877
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81ebfd12-ffffffff81ebfd67: regulator_bulk_disable.cold (STB_LOCAL)
ffffffff818e98d0-ffffffff818e9998: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3fc80)
Location: drivers/regulator/core.c:4917
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81a3fc80-ffffffff81a3fe00: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a89850)
Location: drivers/regulator/core.c:4983
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81a89850-ffffffff81a899d0: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adbfa0)
Location: drivers/regulator/core.c:5005
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81adbfa0-ffffffff81adc120: regulator_bulk_disable (STB_GLOBAL)
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
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010848348)
Location: drivers/regulator/core.c:4506
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffff800010848348-ffff800010848414: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0951b60)
Location: drivers/regulator/core.c:4506
Inline: False
Direct callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_power_off
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_remove
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
```
**Symbols:**

```
c0951b60-c0951c10: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e4f60)
Location: drivers/regulator/core.c:4506
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
c0000000008e4f60-c0000000008e508c: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000528682)
Location: drivers/regulator/core.c:4506
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffe000528682-ffffffe00052873c: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4506
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff816453c7-ffffffff81645415: regulator_bulk_disable.cold (STB_LOCAL)
ffffffff81644000-ffffffff8164405b: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4506
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
```
**Symbols:**

```
ffffffff81625827-ffffffff81625875: regulator_bulk_disable.cold (STB_LOCAL)
ffffffff81624480-ffffffff816244db: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4506
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff81673787-ffffffff816737d5: regulator_bulk_disable.cold (STB_LOCAL)
ffffffff816723e0-ffffffff8167243b: regulator_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_disable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4506
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_remove
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff8168dde7-ffffffff8168de35: regulator_bulk_disable.cold (STB_LOCAL)
ffffffff8168ca40-ffffffff8168ca9b: regulator_bulk_disable (STB_GLOBAL)
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
