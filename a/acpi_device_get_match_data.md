# Function: <code>acpi_device_get_match_data</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81574000)
Location: drivers/acpi/bus.c:833
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff81574000-ffffffff8157402b: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8158bc20)
Location: drivers/acpi/bus.c:802
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff8158bc20-ffffffff8158bc47: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815bc990)
Location: drivers/acpi/bus.c:800
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff815bc990-ffffffff815bca3e: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815ddc50)
Location: drivers/acpi/bus.c:800
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff815ddc50-ffffffff815ddcfe: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816884c0)
Location: drivers/acpi/bus.c:800
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff816884c0-ffffffff8168858b: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816a61e0)
Location: drivers/acpi/bus.c:805
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff816a61e0-ffffffff816a62ae: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81688e60)
Location: drivers/acpi/bus.c:884
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff81688e60-ffffffff81688f33: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816fe2a0)
Location: drivers/acpi/bus.c:886
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff816fe2a0-ffffffff816fe373: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8182bc30)
Location: drivers/acpi/bus.c:923
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff8182bc30-ffffffff8182bcfc: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8195e610)
Location: drivers/acpi/bus.c:929
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff8195e610-ffffffff8195e6dc: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819a4a00)
Location: drivers/acpi/bus.c:902
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff819a4a00-ffffffff819a4acc: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819ed350)
Location: drivers/acpi/bus.c:952
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff819ed350-ffffffff819ed41c: acpi_device_get_match_data (STB_GLOBAL)
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
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffff800010769f80)
Location: drivers/acpi/bus.c:800
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffff800010769f80-ffff80001076a03c: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/ahci_platform.c (0)
Location: include/linux/acpi.h:804
Inline: True
```
</details>
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
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815d0130)
Location: drivers/acpi/bus.c:800
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff815d0130-ffffffff815d01de: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815b9cf0)
Location: drivers/acpi/bus.c:800
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff815b9cf0-ffffffff815b9d9e: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815d1f30)
Location: drivers/acpi/bus.c:800
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff815d1f30-ffffffff815d1fde: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const void *acpi_device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815ebdf0)
Location: drivers/acpi/bus.c:800
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_device_get_match_data
```
**Symbols:**

```
ffffffff815ebdf0-ffffffff815ebe9e: acpi_device_get_match_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
