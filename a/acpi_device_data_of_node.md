# Function: <code>acpi_device_data_of_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct acpi_device_data *acpi_device_data_of_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8148a903)
Location: drivers/acpi/property.c:401
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_node_prop_get
  - drivers/acpi/property.c:acpi_node_prop_read
```
**Symbols:**

```
ffffffff8148a903-ffffffff8148a939: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct acpi_device_data *acpi_device_data_of_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814d9706)
Location: drivers/acpi/property.c:401
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_node_prop_read
  - drivers/acpi/property.c:acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_node_prop_get
```
**Symbols:**

```
ffffffff814d9706-ffffffff814d9741: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct acpi_device_data *acpi_device_data_of_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814fbf78)
Location: drivers/acpi/property.c:454
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_node_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_node_prop_get
```
**Symbols:**

```
ffffffff814fbf78-ffffffff814fbfb3: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device_data *acpi_device_data_of_node(struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150bad0)
Location: drivers/acpi/property.c:470
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff8150bad0-ffffffff8150bb24: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154dce0)
Location: drivers/acpi/property.c:476
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff8154dce0-ffffffff8154dd23: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81584ea0)
Location: drivers/acpi/property.c:476
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff81584ea0-ffffffff81584ee3: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159ccf0)
Location: drivers/acpi/property.c:532
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff8159ccf0-ffffffff8159cd33: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815cdc00)
Location: drivers/acpi/property.c:536
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff815cdc00-ffffffff815cdc43: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815eee80)
Location: drivers/acpi/property.c:536
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff815eee80-ffffffff815eeec3: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169b0c0)
Location: drivers/acpi/property.c:536
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff8169b0c0-ffffffff8169b103: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b7f00)
Location: drivers/acpi/property.c:539
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff816b7f00-ffffffff816b7f43: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81699eb0)
Location: drivers/acpi/property.c:539
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff81699eb0-ffffffff81699ef0: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8170fd50)
Location: drivers/acpi/property.c:539
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff8170fd50-ffffffff8170fd90: acpi_device_data_of_node (STB_LOCAL)
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
Location: drivers/acpi/property.c:545
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
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
Location: drivers/acpi/property.c:704
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
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
Location: drivers/acpi/property.c:704
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
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
Location: drivers/acpi/property.c:708
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
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
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff800010779b98)
Location: drivers/acpi/property.c:536
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffff800010779b98-ffff800010779c00: acpi_device_data_of_node (STB_LOCAL)
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
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ddb10)
Location: drivers/acpi/property.c:536
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff815ddb10-ffffffff815ddb53: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815c9150)
Location: drivers/acpi/property.c:536
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff815c9150-ffffffff815c9193: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e3160)
Location: drivers/acpi/property.c:536
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff815e3160-ffffffff815e31a3: acpi_device_data_of_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct acpi_device_data *acpi_device_data_of_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fd020)
Location: drivers/acpi/property.c:536
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
```
**Symbols:**

```
ffffffff815fd020-ffffffff815fd063: acpi_device_data_of_node (STB_LOCAL)
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
<li>
<b>Return type changed. </b>
<code>struct acpi_device_data *</code> ➡️ <code>const struct acpi_device_data *</code>
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
