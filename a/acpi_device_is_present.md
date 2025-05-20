# Function: <code>acpi_device_is_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool acpi_device_is_present(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814810b4)
Location: drivers/acpi/scan.c:1487
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/scan.c:acpi_bus_attach
```
**Symbols:**

```
ffffffff814810b4-ffffffff814810cd: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool acpi_device_is_present(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814cfae0)
Location: drivers/acpi/scan.c:1545
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/scan.c:acpi_bus_attach
```
**Symbols:**

```
ffffffff814cfae0-ffffffff814cfaf9: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool acpi_device_is_present(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814f1a4a)
Location: drivers/acpi/scan.c:1575
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/scan.c:acpi_bus_attach
```
**Symbols:**

```
ffffffff814f1a4a-ffffffff814f1a63: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814ffad0)
Location: drivers/acpi/scan.c:1604
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff814ffad0-ffffffff814ffae2: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81541c80)
Location: drivers/acpi/scan.c:1703
Inline: True
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff81541c80-ffffffff81541c92: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815755a1)
Location: drivers/acpi/scan.c:1717
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff81577b50-ffffffff81577b62: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8158d3a1)
Location: drivers/acpi/scan.c:1730
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
```
**Symbols:**

```
ffffffff8158f790-ffffffff8158f7a2: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815be161)
Location: drivers/acpi/scan.c:1729
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff815c0400-ffffffff815c0412: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815df421)
Location: drivers/acpi/scan.c:1729
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff815e16c0-ffffffff815e16d2: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168a311)
Location: drivers/acpi/scan.c:1738
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff8168c3b0-ffffffff8168c3c2: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a7ecb)
Location: drivers/acpi/scan.c:1811
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff816aa430-ffffffff816aa445: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168a87b)
Location: drivers/acpi/scan.c:1780
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff8168ccb0-ffffffff8168ccc5: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816fff3b)
Location: drivers/acpi/scan.c:1878
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff817024e0-ffffffff817024f5: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182daaf)
Location: drivers/acpi/scan.c:1921
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff81830240-ffffffff8183025b: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8196088f)
Location: drivers/acpi/scan.c:1905
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff819635d0-ffffffff819635e8: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a6b9f)
Location: drivers/acpi/scan.c:1908
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff819a9a80-ffffffff819a9a98: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819ef5bf)
Location: drivers/acpi/scan.c:1920
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_device_hotplug
Direct callers:
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff819f2520-ffffffff819f2538: acpi_device_is_present (STB_GLOBAL)
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
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076b81c)
Location: drivers/acpi/scan.c:1729
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffff80001076dff8-ffff80001076e02c: acpi_device_is_present (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d15d9)
Location: drivers/acpi/scan.c:1729
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff815d3990-ffffffff815d39a2: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bb199)
Location: drivers/acpi/scan.c:1729
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff815bd550-ffffffff815bd562: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d3701)
Location: drivers/acpi/scan.c:1729
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff815d59a0-ffffffff815d59b2: acpi_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool acpi_device_is_present(const struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815ed5c1)
Location: drivers/acpi/scan.c:1729
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_attach
Direct callers:
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
```
**Symbols:**

```
ffffffff815ef860-ffffffff815ef872: acpi_device_is_present (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct acpi_device *adev</code> ➡️ <code>const struct acpi_device *adev</code>
</li>
</ul>
</details>
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
