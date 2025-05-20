# Function: <code>acpi_data_prop_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_data_prop_read(struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8148aa9c)
Location: drivers/acpi/property.c:718
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_dev_prop_read
  - drivers/acpi/property.c:acpi_node_prop_read
```
**Symbols:**

```
ffffffff8148aa9c-ffffffff8148ac48: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_data_prop_read(struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814d98a0)
Location: drivers/acpi/property.c:718
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_node_prop_read
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff814d98a0-ffffffff814d9a4c: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_data_prop_read(struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814fc14c)
Location: drivers/acpi/property.c:790
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_node_prop_read
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff814fc14c-ffffffff814fc2f8: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_data_prop_read(struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150b810)
Location: drivers/acpi/property.c:816
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff8150b810-ffffffff8150bac4: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154e710)
Location: drivers/acpi/property.c:823
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff8154e710-ffffffff8154e9c4: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81584bf0)
Location: drivers/acpi/property.c:823
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff81584bf0-ffffffff81584e9f: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159d1a0)
Location: drivers/acpi/property.c:911
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff8159d1a0-ffffffff8159d44f: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ce8c0)
Location: drivers/acpi/property.c:929
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff815ce8c0-ffffffff815ceafe: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815efb40)
Location: drivers/acpi/property.c:929
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff815efb40-ffffffff815efd7e: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169be00)
Location: drivers/acpi/property.c:929
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff8169be00-ffffffff8169c03e: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b8c40)
Location: drivers/acpi/property.c:934
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff816b8c40-ffffffff816b8e8d: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169aac0)
Location: drivers/acpi/property.c:920
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff8169aac0-ffffffff8169adee: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81710920)
Location: drivers/acpi/property.c:920
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff81710920-ffffffff81710c4e: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8183f730)
Location: drivers/acpi/property.c:931
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff8183f730-ffffffff8183fa84: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81974a50)
Location: drivers/acpi/property.c:1075
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff81974a50-ffffffff81974e4a: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bb270)
Location: drivers/acpi/property.c:1063
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff819bb270-ffffffff819bb693: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a05aa0)
Location: drivers/acpi/property.c:1130
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
```
**Symbols:**

```
ffffffff81a05aa0-ffffffff81a05ec5: acpi_data_prop_read (STB_LOCAL)
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
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff80001077a9d0)
Location: drivers/acpi/property.c:929
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffff80001077a9d0-ffff80001077ac80: acpi_data_prop_read (STB_LOCAL)
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
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815de7d0)
Location: drivers/acpi/property.c:929
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff815de7d0-ffffffff815dea0e: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815c9e10)
Location: drivers/acpi/property.c:929
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff815c9e10-ffffffff815ca04e: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e3e20)
Location: drivers/acpi/property.c:929
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff815e3e20-ffffffff815e405e: acpi_data_prop_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data *data, const char *propname, enum dev_prop_type proptype, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fdce0)
Location: drivers/acpi/property.c:929
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_dev_prop_read
```
**Symbols:**

```
ffffffff815fdce0-ffffffff815fdf1e: acpi_data_prop_read (STB_LOCAL)
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
<code>struct acpi_device_data *data</code> ➡️ <code>const struct acpi_device_data *data</code>
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
