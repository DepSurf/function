# Function: <code>acpi_data_get_property</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_data_get_property(struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8148a357)
Location: drivers/acpi/property.c:352
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_dev_get_property
  - drivers/acpi/property.c:acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_node_prop_get
```
**Symbols:**

```
ffffffff8148a357-ffffffff8148a40c: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_data_get_property(struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814d9128)
Location: drivers/acpi/property.c:352
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_node_prop_get
  - drivers/acpi/property.c:acpi_dev_get_property
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff814d9128-ffffffff814d91dd: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_data_get_property(struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814fb8b3)
Location: drivers/acpi/property.c:405
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_node_prop_get
  - drivers/acpi/property.c:acpi_dev_get_property
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff814fb8b3-ffffffff814fb968: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_data_get_property(struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150b0e0)
Location: drivers/acpi/property.c:421
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff8150b0e0-ffffffff8150b1b2: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154db70)
Location: drivers/acpi/property.c:426
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff8154db70-ffffffff8154dc42: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81584620)
Location: drivers/acpi/property.c:426
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff81584620-ffffffff815846f2: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159c790)
Location: drivers/acpi/property.c:477
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff8159c790-ffffffff8159c87e: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815cde00)
Location: drivers/acpi/property.c:481
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff815cde00-ffffffff815cdef0: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ef080)
Location: drivers/acpi/property.c:481
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff815ef080-ffffffff815ef170: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169b2c0)
Location: drivers/acpi/property.c:481
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff8169b2c0-ffffffff8169b3b0: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b8100)
Location: drivers/acpi/property.c:484
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff816b8100-ffffffff816b81f0: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169a0a0)
Location: drivers/acpi/property.c:484
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff8169a0a0-ffffffff8169a190: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8170ffa0)
Location: drivers/acpi/property.c:484
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff8170ffa0-ffffffff81710090: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8183ead0)
Location: drivers/acpi/property.c:490
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff8183ead0-ffffffff8183ebd4: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819748e0)
Location: drivers/acpi/property.c:649
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff819748e0-ffffffff819749e4: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bb100)
Location: drivers/acpi/property.c:649
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff819bb100-ffffffff819bb204: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a05930)
Location: drivers/acpi/property.c:653
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff81a05930-ffffffff81a05a34: acpi_data_get_property (STB_LOCAL)
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
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff800010779950)
Location: drivers/acpi/property.c:481
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffff800010779950-ffff800010779a8c: acpi_data_get_property (STB_LOCAL)
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
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ddd10)
Location: drivers/acpi/property.c:481
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff815ddd10-ffffffff815dde00: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815c9350)
Location: drivers/acpi/property.c:481
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff815c9350-ffffffff815c9440: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e3360)
Location: drivers/acpi/property.c:481
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff815e3360-ffffffff815e3450: acpi_data_get_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_data_get_property(const struct acpi_device_data *data, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fd220)
Location: drivers/acpi/property.c:481
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:acpi_data_prop_read
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff815fd220-ffffffff815fd310: acpi_data_get_property (STB_LOCAL)
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
