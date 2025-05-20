# Function: <code>__suspend_report_result</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81558730)
Location: drivers/base/power/main.c:1682
Inline: True
Inline callers:
  - drivers/base/power/main.c:legacy_suspend
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_prepare
Direct callers:
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff81558730-ffffffff81558754: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815ad5dd)
Location: drivers/base/power/main.c:1700
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:legacy_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff815aa830-ffffffff815aa854: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815dc39d)
Location: drivers/base/power/main.c:1775
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:legacy_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff815d9560-ffffffff815d9584: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815f10c2)
Location: drivers/base/power/main.c:1778
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:legacy_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff815ee020-ffffffff815ee045: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816584d9)
Location: drivers/base/power/main.c:1871
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81655310-ffffffff81655335: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff81694577)
Location: drivers/base/power/main.c:2047
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff816943e7-ffffffff81694400: __suspend_report_result.cold.17 (STB_LOCAL)
ffffffff81690ee0-ffffffff81690ef3: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b4bf7)
Location: drivers/base/power/main.c:2053
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff816b4a67-ffffffff816b4a80: __suspend_report_result.cold.18 (STB_LOCAL)
ffffffff816b1540-ffffffff816b1553: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff816eea00)
Location: drivers/base/power/main.c:2041
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff816ee8ff-ffffffff816ee918: __suspend_report_result.cold (STB_LOCAL)
ffffffff816eb280-ffffffff816eb293: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff817129a5)
Location: drivers/base/power/main.c:2062
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff817128df-ffffffff817128f8: __suspend_report_result.cold (STB_LOCAL)
ffffffff8170f240-ffffffff8170f253: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff817ce205)
Location: drivers/base/power/main.c:1939
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff817ce126-ffffffff817ce13f: __suspend_report_result.cold (STB_LOCAL)
ffffffff817ca910-ffffffff817ca923: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff81c0edd8)
Location: drivers/base/power/main.c:1938
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81c0ecfa-ffffffff81c0ed13: __suspend_report_result.cold (STB_LOCAL)
ffffffff817df3c0-ffffffff817df3d3: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff81c00fd6)
Location: drivers/base/power/main.c:1939
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81c00e72-ffffffff81c00e8c: __suspend_report_result.cold (STB_LOCAL)
ffffffff817c3890-ffffffff817c389e: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff81d03b20)
Location: drivers/base/power/main.c:1967
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81d0392c-ffffffff81d03946: __suspend_report_result.cold (STB_LOCAL)
ffffffff8184dc20-ffffffff8184dc2e: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __suspend_report_result(const char *function, struct device *dev, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff81ecc1d8)
Location: drivers/base/power/main.c:1963
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81ecc18a-ffffffff81ecc1c1: __suspend_report_result.part.0 (STB_LOCAL)
ffffffff81ecc1c1-ffffffff81ecc1d8: __suspend_report_result.cold (STB_LOCAL)
ffffffff81993340-ffffffff8199335a: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __suspend_report_result(const char *function, struct device *dev, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b03aa6)
Location: drivers/base/power/main.c:1963
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81b03d30-ffffffff81b03d7d: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __suspend_report_result(const char *function, struct device *dev, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b51b06)
Location: drivers/base/power/main.c:1963
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81b51d90-ffffffff81b51ddd: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __suspend_report_result(const char *function, struct device *dev, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81baa0f6)
Location: drivers/base/power/main.c:1962
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81baa380-ffffffff81baa3cd: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff800010903098)
Location: drivers/base/power/main.c:2062
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffff8000108ff830-ffff8000108ff884: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09ed4a4)
Location: drivers/base/power/main.c:2062
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
c09e9cb8-c09e9cf0: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c0000000009a1748)
Location: drivers/base/power/main.c:2062
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
c00000000099caf0-c00000000099cb40: __suspend_report_result (STB_GLOBAL)
```
</details>
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
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d8d25)
Location: drivers/base/power/main.c:2062
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff816d8c5f-ffffffff816d8c78: __suspend_report_result.cold (STB_LOCAL)
ffffffff816d4f80-ffffffff816d4f93: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b3365)
Location: drivers/base/power/main.c:2062
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff816b329f-ffffffff816b32b8: __suspend_report_result.cold (STB_LOCAL)
ffffffff816afc30-ffffffff816afc43: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff81706665)
Location: drivers/base/power/main.c:2062
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff8170659f-ffffffff817065b8: __suspend_report_result.cold (STB_LOCAL)
ffffffff81702f00-ffffffff81702f13: __suspend_report_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __suspend_report_result(const char *function, void *fn, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff8172109d)
Location: drivers/base/power/main.c:2062
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend
  - drivers/pnp/driver.c:__pnp_bus_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81720faf-ffffffff81720fc8: __suspend_report_result.cold (STB_LOCAL)
ffffffff8171d780-ffffffff8171d793: __suspend_report_result (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>function, fn, ret</code> ➡️ <code>function, dev, fn, ret</code>
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
