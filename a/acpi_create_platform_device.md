# Function: <code>acpi_create_platform_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff8148828e)
Location: drivers/acpi/acpi_platform.c:43
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_default_enumeration
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff8148828e-ffffffff814884ab: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff814d7134)
Location: drivers/acpi/acpi_platform.c:43
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff814d7134-ffffffff814d732c: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff814f97c6)
Location: drivers/acpi/acpi_platform.c:61
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff814f97c6-ffffffff814f9a14: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff81508880)
Location: drivers/acpi/acpi_platform.c:63
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff81508880-ffffffff81508b41: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff8154ac60)
Location: drivers/acpi/acpi_platform.c:63
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff8154ac60-ffffffff8154af21: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff815812b0)
Location: drivers/acpi/acpi_platform.c:63
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff815812b0-ffffffff8158156c: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff81599370)
Location: drivers/acpi/acpi_platform.c:64
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff81599370-ffffffff8159962f: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff815caa00)
Location: drivers/acpi/acpi_platform.c:61
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff815ca780-ffffffff815ca9f2: acpi_create_platform_device.part.0 (STB_LOCAL)
ffffffff815caa52-ffffffff815caa96: acpi_create_platform_device.part.0.cold (STB_LOCAL)
ffffffff815caa00-ffffffff815caa52: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff815ebc80)
Location: drivers/acpi/acpi_platform.c:99
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff815eba00-ffffffff815ebc72: acpi_create_platform_device.part.0 (STB_LOCAL)
ffffffff815ebcd2-ffffffff815ebd16: acpi_create_platform_device.part.0.cold (STB_LOCAL)
ffffffff815ebc80-ffffffff815ebcd2: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff816976f0)
Location: drivers/acpi/acpi_platform.c:99
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff81697470-ffffffff816976e2: acpi_create_platform_device.part.0 (STB_LOCAL)
ffffffff81697742-ffffffff81697786: acpi_create_platform_device.part.0.cold (STB_LOCAL)
ffffffff816976f0-ffffffff81697742: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff816b4840)
Location: drivers/acpi/acpi_platform.c:97
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff816b45c0-ffffffff816b4832: acpi_create_platform_device.part.0 (STB_LOCAL)
ffffffff81c021fb-ffffffff81c0223f: acpi_create_platform_device.part.0.cold (STB_LOCAL)
ffffffff816b4840-ffffffff816b4892: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff81696a70)
Location: drivers/acpi/acpi_platform.c:97
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff816967f0-ffffffff81696a62: acpi_create_platform_device.part.0 (STB_LOCAL)
ffffffff81bf3a2d-ffffffff81bf3a71: acpi_create_platform_device.part.0.cold (STB_LOCAL)
ffffffff81696a70-ffffffff81696ac2: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff8170c810)
Location: drivers/acpi/acpi_platform.c:97
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff8170c590-ffffffff8170c802: acpi_create_platform_device.part.0 (STB_LOCAL)
ffffffff81cf075d-ffffffff81cf07a1: acpi_create_platform_device.part.0.cold (STB_LOCAL)
ffffffff8170c810-ffffffff8170c862: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (0)
Location: drivers/acpi/acpi_platform.c:97
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff81eb85d8-ffffffff81eb8628: acpi_create_platform_device.cold (STB_LOCAL)
ffffffff8183ac50-ffffffff8183af45: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff819702e0)
Location: drivers/acpi/acpi_platform.c:97
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff819702e0-ffffffff81970667: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (0)
Location: drivers/acpi/acpi_platform.c:110
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff82112578-ffffffff8211258d: acpi_create_platform_device.cold (STB_LOCAL)
ffffffff819b6920-ffffffff819b6cb4: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (0)
Location: drivers/acpi/acpi_platform.c:110
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_generic_device_attach
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff821f02e0-ffffffff821f02f5: acpi_create_platform_device.cold (STB_LOCAL)
ffffffff81a00ed0-ffffffff81a01264: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffff800010776ed0)
Location: drivers/acpi/acpi_platform.c:99
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
**Symbols:**

```
ffff800010776ed0-ffff800010777144: acpi_create_platform_device.part.0 (STB_LOCAL)
ffff800010777148-ffff8000107771bc: acpi_create_platform_device (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff815db060)
Location: drivers/acpi/acpi_platform.c:99
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff815dade0-ffffffff815db052: acpi_create_platform_device.part.0 (STB_LOCAL)
ffffffff815db0b2-ffffffff815db0f6: acpi_create_platform_device.part.0.cold (STB_LOCAL)
ffffffff815db060-ffffffff815db0b2: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff815c66a0)
Location: drivers/acpi/acpi_platform.c:99
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff815c6420-ffffffff815c6692: acpi_create_platform_device.part.0 (STB_LOCAL)
ffffffff815c66f2-ffffffff815c6736: acpi_create_platform_device.part.0.cold (STB_LOCAL)
ffffffff815c66a0-ffffffff815c66f2: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff815dff60)
Location: drivers/acpi/acpi_platform.c:99
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff815dfce0-ffffffff815dff52: acpi_create_platform_device.part.0 (STB_LOCAL)
ffffffff815dffb2-ffffffff815dfff6: acpi_create_platform_device.part.0.cold (STB_LOCAL)
ffffffff815dff60-ffffffff815dffb2: acpi_create_platform_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct platform_device *acpi_create_platform_device(struct acpi_device *adev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_platform.c (ffffffff815f9e20)
Location: drivers/acpi/acpi_platform.c:99
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach
```
**Symbols:**

```
ffffffff815f9ba0-ffffffff815f9e12: acpi_create_platform_device.part.0 (STB_LOCAL)
ffffffff815f9e72-ffffffff815f9eb6: acpi_create_platform_device.part.0.cold (STB_LOCAL)
ffffffff815f9e20-ffffffff815f9e72: acpi_create_platform_device (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct property_entry *properties</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct property_entry *properties</code> ➡️ <code>const struct property_entry *properties</code>
</li>
</ul>
</details>
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
