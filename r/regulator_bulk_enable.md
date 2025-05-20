# Function: <code>regulator_bulk_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814da280)
Location: drivers/regulator/core.c:3494
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff814da280-ffffffff814da3ab: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152c960)
Location: drivers/regulator/core.c:3528
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff8152c960-ffffffff8152ca9e: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81558fd0)
Location: drivers/regulator/core.c:3592
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81558fd0-ffffffff815590f7: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156d920)
Location: drivers/regulator/core.c:3615
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff8156d920-ffffffff8156da62: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d1ba0)
Location: drivers/regulator/core.c:3623
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff815d1ba0-ffffffff815d1ce2: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3797
Inline: True
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff8160cc04-ffffffff8160cc17: regulator_bulk_enable.cold.62 (STB_LOCAL)
ffffffff81609e20-ffffffff81609f5c: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81626e22)
Location: drivers/regulator/core.c:4422
Inline: True
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81629202-ffffffff81629215: regulator_bulk_enable.cold.67 (STB_LOCAL)
ffffffff81626d90-ffffffff81626eb1: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4447
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff8165cefb-ffffffff8165cf0f: regulator_bulk_enable.cold (STB_LOCAL)
ffffffff8165a400-ffffffff8165a4ee: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4457
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff8167f722-ffffffff8167f736: regulator_bulk_enable.cold (STB_LOCAL)
ffffffff8167d140-ffffffff8167d22e: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
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
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81730746-ffffffff8173075a: regulator_bulk_enable.cold (STB_LOCAL)
ffffffff8172e4f0-ffffffff8172e5fc: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4644
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81c06c48-ffffffff81c06c5f: regulator_bulk_enable.cold (STB_LOCAL)
ffffffff8174b0c0-ffffffff8174b1cc: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4646
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81bf88e3-ffffffff81bf88fa: regulator_bulk_enable.cold (STB_LOCAL)
ffffffff8172e7d0-ffffffff8172e8de: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4783
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81cf7aed-ffffffff81cf7b04: regulator_bulk_enable.cold (STB_LOCAL)
ffffffff817ae3b0-ffffffff817ae4be: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4828
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81ebfcbf-ffffffff81ebfcd7: regulator_bulk_enable.cold (STB_LOCAL)
ffffffff818e9390-ffffffff818e94c9: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3f6d0)
Location: drivers/regulator/core.c:4868
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81a3f6d0-ffffffff81a3f817: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a892a0)
Location: drivers/regulator/core.c:4934
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81a892a0-ffffffff81a893e7: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adb980)
Location: drivers/regulator/core.c:4956
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81adb980-ffffffff81adbac7: regulator_bulk_enable (STB_GLOBAL)
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010846d10)
Location: drivers/regulator/core.c:4457
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffff800010846d10-ffff800010846e58: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c09504ac)
Location: drivers/regulator/core.c:4457
Inline: False
Direct callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
```
**Symbols:**

```
c09504ac-c09505cc: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e2e50)
Location: drivers/regulator/core.c:4457
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
c0000000008e2e50-c0000000008e2fe4: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005271c2)
Location: drivers/regulator/core.c:4457
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffe0005271c2-ffffffe0005272b4: regulator_bulk_enable (STB_GLOBAL)
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
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4457
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff8164513b-ffffffff8164514f: regulator_bulk_enable.cold (STB_LOCAL)
ffffffff81642a20-ffffffff81642b0e: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4457
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
```
**Symbols:**

```
ffffffff81625602-ffffffff81625616: regulator_bulk_enable.cold (STB_LOCAL)
ffffffff81623020-ffffffff8162310e: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4457
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff81673562-ffffffff81673576: regulator_bulk_enable.cold (STB_LOCAL)
ffffffff81670f80-ffffffff8167106e: regulator_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_enable(int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4457
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
**Symbols:**

```
ffffffff8168dbc2-ffffffff8168dbd6: regulator_bulk_enable.cold (STB_LOCAL)
ffffffff8168b5e0-ffffffff8168b6ce: regulator_bulk_enable (STB_GLOBAL)
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
