# Function: <code>__dev_fwnode_const</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct fwnode_handle *__dev_fwnode_const(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af5255)
Location: drivers/base/property.c:27
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_named_child_node
Direct callers:
  - drivers/usb/roles/class.c:usb_role_switch_get
```
**Symbols:**

```
ffffffff81af4690-ffffffff81af46a8: __dev_fwnode_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct fwnode_handle *__dev_fwnode_const(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b43485)
Location: drivers/base/property.c:27
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/usb/roles/class.c:usb_role_switch_get
```
**Symbols:**

```
ffffffff81b428a0-ffffffff81b428b8: __dev_fwnode_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct fwnode_handle *__dev_fwnode_const(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9b355)
Location: drivers/base/property.c:27
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/usb/roles/class.c:usb_role_switch_get
```
**Symbols:**

```
ffffffff81b9a770-ffffffff81b9a788: __dev_fwnode_const (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
