# Function: <code>acpi_match_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8147ebbe)
Location: drivers/acpi/bus.c:667
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/mfd/axp20x.c:axp20x_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff8147ebbe-ffffffff8147ebe3: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814cd415)
Location: drivers/acpi/bus.c:743
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff814cd415-ffffffff814cd43a: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814ef343)
Location: drivers/acpi/bus.c:753
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
**Symbols:**

```
ffffffff814ef343-ffffffff814ef368: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814fc310)
Location: drivers/acpi/bus.c:781
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff814fc310-ffffffff814fc335: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8153e130)
Location: drivers/acpi/bus.c:808
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cannonlake.c:cnl_pinctrl_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8153e130-ffffffff8153e155: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81573f90)
Location: drivers/acpi/bus.c:823
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/acpi/bus.c:acpi_device_get_match_data
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81573f90-ffffffff81573ffb: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8158bbb0)
Location: drivers/acpi/bus.c:792
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/acpi/bus.c:acpi_device_get_match_data
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device
```
**Symbols:**

```
ffffffff8158bbb0-ffffffff8158bc1b: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815bc920)
Location: drivers/acpi/bus.c:779
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device
```
**Symbols:**

```
ffffffff815bc920-ffffffff815bc98d: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815ddbe0)
Location: drivers/acpi/bus.c:779
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device
```
**Symbols:**

```
ffffffff815ddbe0-ffffffff815ddc4d: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816884ef)
Location: drivers/acpi/bus.c:779
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_get_match_data
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device
```
**Symbols:**

```
ffffffff816883d0-ffffffff8168843b: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816a620f)
Location: drivers/acpi/bus.c:784
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_get_match_data
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
```
**Symbols:**

```
ffffffff816a60f0-ffffffff816a615e: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81688e8f)
Location: drivers/acpi/bus.c:863
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_get_match_data
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff81688d60-ffffffff81688dd2: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816fe2cf)
Location: drivers/acpi/bus.c:865
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_get_match_data
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff816fe1a0-ffffffff816fe212: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8182bc5f)
Location: drivers/acpi/bus.c:902
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_get_match_data
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff8182bb40-ffffffff8182bbab: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8195e63f)
Location: drivers/acpi/bus.c:908
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_get_match_data
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff8195e500-ffffffff8195e56b: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819a4a2f)
Location: drivers/acpi/bus.c:884
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_get_match_data
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/usb/dwc2/params.c:dwc2_init_params
```
**Symbols:**

```
ffffffff819a48f0-ffffffff819a495b: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819ed37f)
Location: drivers/acpi/bus.c:934
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_device_get_match_data
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
```
**Symbols:**

```
ffffffff819ed240-ffffffff819ed2ab: acpi_match_device (STB_GLOBAL)
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
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffff800010769ef8)
Location: drivers/acpi/bus.c:779
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device
```
**Symbols:**

```
ffff800010769ef8-ffff800010769f7c: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815d00c0)
Location: drivers/acpi/bus.c:779
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
```
**Symbols:**

```
ffffffff815d00c0-ffffffff815d012d: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815b9c80)
Location: drivers/acpi/bus.c:779
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
```
**Symbols:**

```
ffffffff815b9c80-ffffffff815b9ced: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815d1ec0)
Location: drivers/acpi/bus.c:779
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device
```
**Symbols:**

```
ffffffff815d1ec0-ffffffff815d1f2d: acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct acpi_device_id *acpi_match_device(const struct acpi_device_id *ids, const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815ebd80)
Location: drivers/acpi/bus.c:779
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/char/tpm/tpm_tis.c:check_acpi_tpm2
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_match_device
```
**Symbols:**

```
ffffffff815ebd80-ffffffff815ebded: acpi_match_device (STB_GLOBAL)
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
