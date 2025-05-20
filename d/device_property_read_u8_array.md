# Function: <code>device_property_read_u8_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81551b00)
Location: drivers/base/property.c:245
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_addr
```
**Symbols:**

```
ffffffff81551b00-ffffffff81551b17: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a36af)
Location: drivers/base/property.c:251
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_addr
```
**Symbols:**

```
ffffffff815a3680-ffffffff815a3697: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d1dbf)
Location: drivers/base/property.c:251
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_addr
```
**Symbols:**

```
ffffffff815d1d90-ffffffff815d1da7: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6220)
Location: drivers/base/property.c:283
Inline: True
```
**Symbols:**

```
ffffffff815e6220-ffffffff815e6242: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d590)
Location: drivers/base/property.c:292
Inline: True
```
**Symbols:**

```
ffffffff8164d590-ffffffff8164d5b2: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816887d0)
Location: drivers/base/property.c:353
Inline: False
```
**Symbols:**

```
ffffffff816887d0-ffffffff816887f2: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a84c0)
Location: drivers/base/property.c:78
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff816a84c0-ffffffff816a84e2: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1cd0)
Location: drivers/base/property.c:78
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff816e1cd0-ffffffff816e1cf2: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705e80)
Location: drivers/base/property.c:78
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff81705e80-ffffffff81705ea2: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0540)
Location: drivers/base/property.c:78
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff817c0540-ffffffff817c0562: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5400)
Location: drivers/base/property.c:78
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff817d5400-ffffffff817d5422: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b8e40)
Location: drivers/base/property.c:78
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff817b8e40-ffffffff817b8e62: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81842aa0)
Location: drivers/base/property.c:78
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff81842aa0-ffffffff81842ac2: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff819862f0)
Location: drivers/base/property.c:82
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff819862f0-ffffffff81986321: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af48e0)
Location: drivers/base/property.c:89
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff81af48e0-ffffffff81af4911: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_property_read_u8_array(const struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b42af0)
Location: drivers/base/property.c:93
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff81b42af0-ffffffff81b42b21: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_property_read_u8_array(const struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9a9c0)
Location: drivers/base/property.c:93
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff81b9a9c0-ffffffff81b9a9f1: device_property_read_u8_array (STB_GLOBAL)
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
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2a90)
Location: drivers/base/property.c:78
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffff8000108f2a90-ffff8000108f2af0: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df6f0)
Location: drivers/base/property.c:78
Inline: False
```
**Symbols:**

```
c09df6f0-c09df730: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c800)
Location: drivers/base/property.c:78
Inline: False
```
**Symbols:**

```
c00000000098c800-c00000000098c840: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe00058456c)
Location: drivers/base/property.c:78
Inline: False
```
**Symbols:**

```
ffffffe00058456c-ffffffe0005845be: device_property_read_u8_array (STB_GLOBAL)
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
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb5d0)
Location: drivers/base/property.c:78
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff816cb5d0-ffffffff816cb5f2: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6900)
Location: drivers/base/property.c:78
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff816a6900-ffffffff816a6922: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9b40)
Location: drivers/base/property.c:78
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff816f9b40-ffffffff816f9b62: device_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_property_read_u8_array(struct device *dev, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817143e0)
Location: drivers/base/property.c:78
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff817143e0-ffffffff81714402: device_property_read_u8_array (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device *dev</code> ➡️ <code>const struct device *dev</code>
</li>
</ul>
</details>
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
