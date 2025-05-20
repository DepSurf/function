# Function: <code>acpi_node_prop_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_node_prop_read(struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8148aee5)
Location: drivers/acpi/property.c:788
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:__fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u32_array
```
**Symbols:**

```
ffffffff8148aee5-ffffffff8148af1f: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_node_prop_read(struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814d9cfb)
Location: drivers/acpi/property.c:788
Inline: False
Direct callers:
  - drivers/base/property.c:__fwnode_property_read_string
  - drivers/base/property.c:__fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u8_array
```
**Symbols:**

```
ffffffff814d9cfb-ffffffff814d9d35: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_node_prop_read(struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814fc5a7)
Location: drivers/acpi/property.c:860
Inline: False
Direct callers:
  - drivers/base/property.c:__fwnode_property_read_string
  - drivers/base/property.c:__fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u8_array
```
**Symbols:**

```
ffffffff814fc5a7-ffffffff814fc5e1: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_read(struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150bda7)
Location: drivers/acpi/property.c:888
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff8150c640-ffffffff8150c684: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154e9e7)
Location: drivers/acpi/property.c:895
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff8154f240-ffffffff8154f284: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815851d5)
Location: drivers/acpi/property.c:895
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff81585ae0-ffffffff81585b1e: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159d455)
Location: drivers/acpi/property.c:983
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff8159e060-ffffffff8159e09e: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ceb05)
Location: drivers/acpi/property.c:1001
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff815cf580-ffffffff815cf5be: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815efd85)
Location: drivers/acpi/property.c:1001
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff815f0800-ffffffff815f083e: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169c075)
Location: drivers/acpi/property.c:1001
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff8169ca80-ffffffff8169cabe: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b8ed7)
Location: drivers/acpi/property.c:1016
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff816b9920-ffffffff816b995e: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169ae87)
Location: drivers/acpi/property.c:996
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81710ce7)
Location: drivers/acpi/property.c:996
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81840149)
Location: drivers/acpi/property.c:1007
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819767f9)
Location: drivers/acpi/property.c:1174
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bd049)
Location: drivers/acpi/property.c:1162
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a072c9)
Location: drivers/acpi/property.c:1230
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
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
int acpi_node_prop_read(const struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff80001077aca8)
Location: drivers/acpi/property.c:1001
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffff80001077b880-ffff80001077b8e0: acpi_node_prop_read (STB_GLOBAL)
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
int acpi_node_prop_read(const struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815dea15)
Location: drivers/acpi/property.c:1001
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff815df490-ffffffff815df4ce: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ca055)
Location: drivers/acpi/property.c:1001
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff815caad0-ffffffff815cab0e: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e4065)
Location: drivers/acpi/property.c:1001
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff815e4ae0-ffffffff815e4b1e: acpi_node_prop_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle *fwnode, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fdf25)
Location: drivers/acpi/property.c:1001
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff815fe9a0-ffffffff815fe9de: acpi_node_prop_read (STB_GLOBAL)
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
