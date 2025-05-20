# Function: <code>device_add_properties</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a3c30)
Location: drivers/base/property.c:850
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
```
**Symbols:**

```
ffffffff815a3c30-ffffffff815a3ec1: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d2340)
Location: drivers/base/property.c:850
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff815d2340-ffffffff815d25d1: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6ff0)
Location: drivers/base/property.c:889
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff815e6ff0-ffffffff815e7093: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164e3c0)
Location: drivers/base/property.c:931
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
**Symbols:**

```
ffffffff8164e3c0-ffffffff8164e461: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81689bf0)
Location: drivers/base/property.c:991
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff81689bf0-ffffffff81689c98: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8ba0)
Location: drivers/base/property.c:521
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff816a8ba0-ffffffff816a8bcf: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1fb0)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff816e1fb0-ffffffff816e1fe1: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81706160)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff81706160-ffffffff81706191: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c07f0)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff817c07f0-ffffffff817c0823: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5690)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff817d5690-ffffffff817d56c3: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b90d0)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff817b90d0-ffffffff817b9103: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81842d30)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_huawei_pcie_sva
```
**Symbols:**

```
ffffffff81842d30-ffffffff81842d63: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f3008)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffff8000108f3008-ffff8000108f3054: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09dfa84)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
c09dfa84-c09dfac8: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098cc90)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
c00000000098cc90-c00000000098cd18: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe0005849c6)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffe0005849c6-ffffffe000584a0e: device_add_properties (STB_GLOBAL)
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
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb8b0)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff816cb8b0-ffffffff816cb8e1: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6be0)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff816a6be0-ffffffff816a6c11: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9e20)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff816f9e20-ffffffff816f9e51: device_add_properties (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_add_properties(struct device *dev, const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817146c0)
Location: drivers/base/property.c:545
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff817146c0-ffffffff817146f1: device_add_properties (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct property_entry *properties</code> ➡️ <code>const struct property_entry *properties</code>
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
