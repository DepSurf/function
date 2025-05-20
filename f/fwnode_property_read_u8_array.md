# Function: <code>fwnode_property_read_u8_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fwnode_property_read_u8_array(struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815519e0)
Location: drivers/base/property.c:450
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_mac_addr
```
**Symbols:**

```
ffffffff815519e0-ffffffff81551af7: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fwnode_property_read_u8_array(struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a3530)
Location: drivers/base/property.c:457
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_mac_addr
```
**Symbols:**

```
ffffffff815a3530-ffffffff815a3677: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fwnode_property_read_u8_array(struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d1c40)
Location: drivers/base/property.c:457
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_mac_addr
```
**Symbols:**

```
ffffffff815d1c40-ffffffff815d1d87: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6200)
Location: drivers/base/property.c:470
Inline: True
```
**Symbols:**

```
ffffffff815e6200-ffffffff815e621b: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d570)
Location: drivers/base/property.c:479
Inline: True
```
**Symbols:**

```
ffffffff8164d570-ffffffff8164d58b: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688c15)
Location: drivers/base/property.c:540
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff81688890-ffffffff816888ab: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8915)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff816a8580-ffffffff816a859b: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1d05)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff816e1cb0-ffffffff816e1ccb: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705eb5)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff81705e60-ffffffff81705e7b: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0d35)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff817c0520-ffffffff817c053b: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5ae8)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff817d53e0-ffffffff817d53fb: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9508)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff817b8e20-ffffffff817b8e3b: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81843168)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_property_read_u8_array
Direct callers:
  - drivers/acpi/device_pm.c:acpi_storage_d3
```
**Symbols:**

```
ffffffff81842a80-ffffffff81842a9b: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986300)
Location: drivers/base/property.c:285
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u8_array
Direct callers:
  - drivers/acpi/device_pm.c:acpi_storage_d3
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
```
**Symbols:**

```
ffffffff819862c0-ffffffff819862ea: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af48f0)
Location: drivers/base/property.c:292
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u8_array
Direct callers:
  - drivers/acpi/device_pm.c:acpi_storage_d3
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
```
**Symbols:**

```
ffffffff81af48a0-ffffffff81af48ca: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b42b00)
Location: drivers/base/property.c:296
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u8_array
Direct callers:
  - drivers/acpi/device_pm.c:acpi_storage_d3
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
```
**Symbols:**

```
ffffffff81b42ab0-ffffffff81b42ada: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9a9d0)
Location: drivers/base/property.c:296
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u8_array
Direct callers:
  - drivers/acpi/device_pm.c:acpi_storage_d3
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
```
**Symbols:**

```
ffffffff81b9a980-ffffffff81b9a9aa: fwnode_property_read_u8_array (STB_GLOBAL)
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
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2b18)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffff8000108f2a40-ffff8000108f2a90: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df748)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
c09df6bc-c09df6f0: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c828)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
c00000000098c7d0-c00000000098c7f4: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584598)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffe000584528-ffffffe00058456c: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb605)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff816cb5b0-ffffffff816cb5cb: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6935)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff816a68e0-ffffffff816a68fb: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9b75)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff816f9b20-ffffffff816f9b3b: fwnode_property_read_u8_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u8_array(const struct fwnode_handle *fwnode, const char *propname, u8 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714415)
Location: drivers/base/property.c:265
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff817143c0-ffffffff817143db: fwnode_property_read_u8_array (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle *fwnode</code> ➡️ <code>const struct fwnode_handle *fwnode</code>
</li>
</ul>
</details>
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
