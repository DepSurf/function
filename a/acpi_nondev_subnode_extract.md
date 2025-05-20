# Function: <code>acpi_nondev_subnode_extract</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/property.c (ffffffff814fbc49)
Location: drivers/acpi/property.c:44
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff814fbc49-ffffffff814fbd79: acpi_nondev_subnode_extract.isra.4 (STB_LOCAL)
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
In drivers/acpi/property.c (ffffffff8150bed0)
Location: drivers/acpi/property.c:45
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff8150bed0-ffffffff8150c08a: acpi_nondev_subnode_extract.isra.7 (STB_LOCAL)
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
In drivers/acpi/property.c (ffffffff8154ec20)
Location: drivers/acpi/property.c:43
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff8154ec20-ffffffff8154edd2: acpi_nondev_subnode_extract.isra.7 (STB_LOCAL)
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
In drivers/acpi/property.c (ffffffff815854f0)
Location: drivers/acpi/property.c:43
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff815854f0-ffffffff8158567d: acpi_nondev_subnode_extract.isra.7 (STB_LOCAL)
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
In drivers/acpi/property.c (ffffffff8159d870)
Location: drivers/acpi/property.c:58
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff8159d870-ffffffff8159da10: acpi_nondev_subnode_extract.isra.10 (STB_LOCAL)
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
In drivers/acpi/property.c (ffffffff815ced80)
Location: drivers/acpi/property.c:62
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff815ced80-ffffffff815cef31: acpi_nondev_subnode_extract.isra.0 (STB_LOCAL)
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
In drivers/acpi/property.c (ffffffff815f0000)
Location: drivers/acpi/property.c:62
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff815f0000-ffffffff815f01b1: acpi_nondev_subnode_extract.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool acpi_nondev_subnode_extract(const union acpi_object *desc, acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169c250)
Location: drivers/acpi/property.c:62
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_add_nondev_subnodes
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff8169c250-ffffffff8169c3bd: acpi_nondev_subnode_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool acpi_nondev_subnode_extract(const union acpi_object *desc, acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b90a0)
Location: drivers/acpi/property.c:65
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_add_nondev_subnodes
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff816b90a0-ffffffff816b924c: acpi_nondev_subnode_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool acpi_nondev_subnode_extract(const union acpi_object *desc, acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169b0a0)
Location: drivers/acpi/property.c:65
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff8169b0a0-ffffffff8169b24c: acpi_nondev_subnode_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool acpi_nondev_subnode_extract(const union acpi_object *desc, acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81710f40)
Location: drivers/acpi/property.c:65
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff81710f40-ffffffff817110e9: acpi_nondev_subnode_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_nondev_subnode_extract(const union acpi_object *desc, acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8183fcb0)
Location: drivers/acpi/property.c:65
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff8183fcb0-ffffffff8183fe77: acpi_nondev_subnode_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_nondev_subnode_extract(union acpi_object *desc, acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81976280)
Location: drivers/acpi/property.c:70
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff81976280-ffffffff81976449: acpi_nondev_subnode_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_nondev_subnode_extract(union acpi_object *desc, acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bcbf0)
Location: drivers/acpi/property.c:70
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff819bcbf0-ffffffff819bcdb1: acpi_nondev_subnode_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_nondev_subnode_extract(union acpi_object *desc, acpi_handle handle, const union acpi_object *link, struct list_head *list, struct fwnode_handle *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a07a80)
Location: drivers/acpi/property.c:74
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff81a07a80-ffffffff81a07c6e: acpi_nondev_subnode_extract (STB_LOCAL)
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
In drivers/acpi/property.c (ffff80001077afa8)
Location: drivers/acpi/property.c:62
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffff80001077afa8-ffff80001077b16c: acpi_nondev_subnode_extract.isra.0 (STB_LOCAL)
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
In drivers/acpi/property.c (ffffffff815dec90)
Location: drivers/acpi/property.c:62
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff815dec90-ffffffff815dee41: acpi_nondev_subnode_extract.isra.0 (STB_LOCAL)
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
In drivers/acpi/property.c (ffffffff815ca2d0)
Location: drivers/acpi/property.c:62
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff815ca2d0-ffffffff815ca481: acpi_nondev_subnode_extract.isra.0 (STB_LOCAL)
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
In drivers/acpi/property.c (ffffffff815e42e0)
Location: drivers/acpi/property.c:62
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff815e42e0-ffffffff815e4491: acpi_nondev_subnode_extract.isra.0 (STB_LOCAL)
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
In drivers/acpi/property.c (ffffffff815fe1a0)
Location: drivers/acpi/property.c:62
Inline: True
Direct callers:
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
**Symbols:**

```
ffffffff815fe1a0-ffffffff815fe351: acpi_nondev_subnode_extract.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
