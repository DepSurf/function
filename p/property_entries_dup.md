# Function: <code>property_entries_dup</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6d30)
Location: drivers/base/property.c:758
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffffffff815e6d30-ffffffff815e6fef: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164e100)
Location: drivers/base/property.c:799
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffffffff8164e100-ffffffff8164e3bf: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816898e0)
Location: drivers/base/property.c:859
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffffffff816898e0-ffffffff81689beb: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816aa5b0)
Location: drivers/base/swnode.c:380
Inline: False
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffffffff816aa5b0-ffffffff816aa8ea: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e469e)
Location: drivers/base/swnode.c:419
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffffffff816e4300-ffffffff816e4617: property_entries_dup.part.0 (STB_LOCAL)
ffffffff816e4620-ffffffff816e4638: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff8170866e)
Location: drivers/base/swnode.c:419
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffffffff817082d0-ffffffff817085e7: property_entries_dup.part.0 (STB_LOCAL)
ffffffff817085f0-ffffffff81708608: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c3049)
Location: drivers/base/swnode.c:296
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffffffff817c2c90-ffffffff817c2da1: property_entries_dup.part.0 (STB_LOCAL)
ffffffff817c2db0-ffffffff817c2dc8: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d7e89)
Location: drivers/base/swnode.c:296
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffffffff817d7aa0-ffffffff817d7bb1: property_entries_dup.part.0 (STB_LOCAL)
ffffffff817d7bc0-ffffffff817d7bd8: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bc18a)
Location: drivers/base/swnode.c:310
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
```
**Symbols:**

```
ffffffff817bb680-ffffffff817bb77b: property_entries_dup.part.0 (STB_LOCAL)
ffffffff817bb780-ffffffff817bb798: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff8184647a)
Location: drivers/base/swnode.c:312
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
```
**Symbols:**

```
ffffffff81845bd0-ffffffff81845ccb: property_entries_dup.part.0 (STB_LOCAL)
ffffffff81845cd0-ffffffff81845ce8: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198a5e2)
Location: drivers/base/swnode.c:312
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
```
**Symbols:**

```
ffffffff81989f30-ffffffff8198a058: property_entries_dup.part.0 (STB_LOCAL)
ffffffff8198a060-ffffffff8198a084: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff81af9a22)
Location: drivers/base/swnode.c:312
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
```
**Symbols:**

```
ffffffff81af9420-ffffffff81af9548: property_entries_dup.part.0 (STB_LOCAL)
ffffffff81af9560-ffffffff81af9584: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b47fd2)
Location: drivers/base/swnode.c:312
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
```
**Symbols:**

```
ffffffff81b479e0-ffffffff81b47af2: property_entries_dup.part.0 (STB_LOCAL)
ffffffff81b47b10-ffffffff81b47b34: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff81ba0362)
Location: drivers/base/swnode.c:312
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
```
**Symbols:**

```
ffffffff81b9fd70-ffffffff81b9fe82: property_entries_dup.part.0 (STB_LOCAL)
ffffffff81b9fea0-ffffffff81b9fec4: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f6698)
Location: drivers/base/swnode.c:419
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffff8000108f62b8-ffff8000108f65f0: property_entries_dup.part.0 (STB_LOCAL)
ffff8000108f65f0-ffff8000108f6628: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (c09e26f4)
Location: drivers/base/swnode.c:419
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
c09e2380-c09e2660: property_entries_dup.part.0 (STB_LOCAL)
c09e2660-c09e268c: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (c0000000009919a4)
Location: drivers/base/swnode.c:419
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
c0000000009914b0-c0000000009918e4: property_entries_dup.part.0 (STB_LOCAL)
c0000000009918f0-c00000000099190c: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffe0005875b0)
Location: drivers/base/swnode.c:419
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffffffe000587276-ffffffe00058751c: property_entries_dup.part.0 (STB_LOCAL)
ffffffe00058751c-ffffffe00058754c: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cddbe)
Location: drivers/base/swnode.c:419
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffffffff816cda20-ffffffff816cdd37: property_entries_dup.part.0 (STB_LOCAL)
ffffffff816cdd40-ffffffff816cdd58: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a90ee)
Location: drivers/base/swnode.c:419
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffffffff816a8d50-ffffffff816a9067: property_entries_dup.part.0 (STB_LOCAL)
ffffffff816a9070-ffffffff816a9088: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fc32e)
Location: drivers/base/swnode.c:419
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffffffff816fbf90-ffffffff816fc2a7: property_entries_dup.part.0 (STB_LOCAL)
ffffffff816fc2b0-ffffffff816fc2c8: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct property_entry *property_entries_dup(const struct property_entry *properties);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff81716ece)
Location: drivers/base/swnode.c:419
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
**Symbols:**

```
ffffffff81716b30-ffffffff81716e47: property_entries_dup.part.0 (STB_LOCAL)
ffffffff81716e50-ffffffff81716e68: property_entries_dup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
