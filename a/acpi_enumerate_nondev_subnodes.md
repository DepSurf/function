# Function: <code>acpi_enumerate_nondev_subnodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool acpi_enumerate_nondev_subnodes(acpi_handle scope, const union acpi_object *desc, struct acpi_device_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8148a6be)
Location: drivers/acpi/property.c:120
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff8148a6be-ffffffff8148a903: acpi_enumerate_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool acpi_enumerate_nondev_subnodes(acpi_handle scope, const union acpi_object *desc, struct acpi_device_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814d94be)
Location: drivers/acpi/property.c:120
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
**Symbols:**

```
ffffffff814d94be-ffffffff814d9706: acpi_enumerate_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool acpi_enumerate_nondev_subnodes(acpi_handle scope, const union acpi_object *desc, struct acpi_device_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814fbe11)
Location: drivers/acpi/property.c:173
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff814fbe11-ffffffff814fbf78: acpi_enumerate_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150c140)
Location: drivers/acpi/property.c:186
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff8150c140-ffffffff8150c2c5: acpi_enumerate_nondev_subnodes.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154ea90)
Location: drivers/acpi/property.c:183
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff8154ea90-ffffffff8154ec19: acpi_enumerate_nondev_subnodes.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/property.c (ffffffff8158582b)
Location: drivers/acpi/property.c:183
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff81585360-ffffffff815854ec: acpi_enumerate_nondev_subnodes.isra.9.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159dd5c)
Location: drivers/acpi/property.c:199
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff8159dac0-ffffffff8159dc4c: acpi_enumerate_nondev_subnodes.isra.12.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ceff0)
Location: drivers/acpi/property.c:203
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff815ceff0-ffffffff815cf169: acpi_enumerate_nondev_subnodes.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/property.c (ffffffff815f0270)
Location: drivers/acpi/property.c:203
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff815f0270-ffffffff815f03e9: acpi_enumerate_nondev_subnodes.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool acpi_enumerate_nondev_subnodes(acpi_handle scope, const union acpi_object *desc, struct acpi_device_data *data, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169c590)
Location: drivers/acpi/property.c:203
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
**Symbols:**

```
ffffffff8169c590-ffffffff8169c62d: acpi_enumerate_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool acpi_enumerate_nondev_subnodes(acpi_handle scope, const union acpi_object *desc, struct acpi_device_data *data, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b9420)
Location: drivers/acpi/property.c:206
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
**Symbols:**

```
ffffffff816b9420-ffffffff816b94bd: acpi_enumerate_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool acpi_enumerate_nondev_subnodes(acpi_handle scope, const union acpi_object *desc, struct acpi_device_data *data, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169b300)
Location: drivers/acpi/property.c:206
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
**Symbols:**

```
ffffffff8169b300-ffffffff8169b481: acpi_enumerate_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool acpi_enumerate_nondev_subnodes(acpi_handle scope, const union acpi_object *desc, struct acpi_device_data *data, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff817111a0)
Location: drivers/acpi/property.c:206
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
**Symbols:**

```
ffffffff817111a0-ffffffff81711321: acpi_enumerate_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_enumerate_nondev_subnodes(acpi_handle scope, const union acpi_object *desc, struct acpi_device_data *data, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8183ff30)
Location: drivers/acpi/property.c:206
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
**Symbols:**

```
ffffffff8183ff30-ffffffff818400ca: acpi_enumerate_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_enumerate_nondev_subnodes(acpi_handle scope, union acpi_object *desc, struct acpi_device_data *data, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81976520)
Location: drivers/acpi/property.c:211
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
**Symbols:**

```
ffffffff81976520-ffffffff819766ba: acpi_enumerate_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_enumerate_nondev_subnodes(acpi_handle scope, union acpi_object *desc, struct acpi_device_data *data, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bce90)
Location: drivers/acpi/property.c:211
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
**Symbols:**

```
ffffffff819bce90-ffffffff819bd025: acpi_enumerate_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_enumerate_nondev_subnodes(acpi_handle scope, union acpi_object *desc, struct acpi_device_data *data, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a07d40)
Location: drivers/acpi/property.c:215
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
**Symbols:**

```
ffffffff81a07d40-ffffffff81a07ed5: acpi_enumerate_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/property.c (ffff80001077b230)
Location: drivers/acpi/property.c:203
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffff80001077b230-ffff80001077b420: acpi_enumerate_nondev_subnodes.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/property.c (ffffffff815def00)
Location: drivers/acpi/property.c:203
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff815def00-ffffffff815df079: acpi_enumerate_nondev_subnodes.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ca540)
Location: drivers/acpi/property.c:203
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff815ca540-ffffffff815ca6b9: acpi_enumerate_nondev_subnodes.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e4550)
Location: drivers/acpi/property.c:203
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff815e4550-ffffffff815e46c9: acpi_enumerate_nondev_subnodes.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fe410)
Location: drivers/acpi/property.c:203
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff815fe410-ffffffff815fe589: acpi_enumerate_nondev_subnodes.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const union acpi_object *desc</code> ➡️ <code>union acpi_object *desc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
