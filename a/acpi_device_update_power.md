# Function: <code>acpi_device_update_power</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8147d735)
Location: drivers/acpi/device_pm.c:322
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/fan.c:acpi_fan_probe
```
**Symbols:**

```
ffffffff8147d735-ffffffff8147d7fc: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814cbef8)
Location: drivers/acpi/device_pm.c:324
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff814cbef8-ffffffff814cbfc9: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814ede26)
Location: drivers/acpi/device_pm.c:324
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff814ede26-ffffffff814edef7: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814facf0)
Location: drivers/acpi/device_pm.c:327
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff814facf0-ffffffff814fadc3: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153c940)
Location: drivers/acpi/device_pm.c:327
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff8153c940-ffffffff8153ca13: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815727f0)
Location: drivers/acpi/device_pm.c:327
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff815727f0-ffffffff815728c3: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8158a400)
Location: drivers/acpi/device_pm.c:328
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff8158a400-ffffffff8158a4d3: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815bb0e0)
Location: drivers/acpi/device_pm.c:369
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff815bb0e0-ffffffff815bb1b5: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815dc3b0)
Location: drivers/acpi/device_pm.c:373
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff815dc3b0-ffffffff815dc485: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81686870)
Location: drivers/acpi/device_pm.c:373
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff81686870-ffffffff81686945: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816a4620)
Location: drivers/acpi/device_pm.c:373
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff816a4620-ffffffff816a46f5: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816873a0)
Location: drivers/acpi/device_pm.c:370
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff816873a0-ffffffff8168747b: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816fc820)
Location: drivers/acpi/device_pm.c:370
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff816fc820-ffffffff816fc8fb: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81829f20)
Location: drivers/acpi/device_pm.c:372
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff81829f20-ffffffff81829fff: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195c360)
Location: drivers/acpi/device_pm.c:400
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff8195c360-ffffffff8195c43f: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a2840)
Location: drivers/acpi/device_pm.c:400
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff819a2840-ffffffff819a2929: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819eaef0)
Location: drivers/acpi/device_pm.c:413
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff819eaef0-ffffffff819eafd9: acpi_device_update_power (STB_GLOBAL)
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
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffff800010768a20)
Location: drivers/acpi/device_pm.c:373
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffff800010768a20-ffff800010768b18: acpi_device_update_power (STB_GLOBAL)
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
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cea00)
Location: drivers/acpi/device_pm.c:373
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
```
**Symbols:**

```
ffffffff815cea00-ffffffff815cead5: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b85c0)
Location: drivers/acpi/device_pm.c:373
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
```
**Symbols:**

```
ffffffff815b85c0-ffffffff815b8695: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815d0690)
Location: drivers/acpi/device_pm.c:373
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff815d0690-ffffffff815d0765: acpi_device_update_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_device_update_power(struct acpi_device *device, int *state_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ea550)
Location: drivers/acpi/device_pm.c:373
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff815ea550-ffffffff815ea625: acpi_device_update_power (STB_GLOBAL)
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
