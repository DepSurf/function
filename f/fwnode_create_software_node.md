# Function: <code>fwnode_create_software_node</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816aa8f0)
Location: drivers/base/swnode.c:552
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
```
**Symbols:**

```
ffffffff816aa8f0-ffffffff816aaae8: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e4640)
Location: drivers/base/swnode.c:769
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
```
**Symbols:**

```
ffffffff816e4640-ffffffff816e4707: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81708610)
Location: drivers/base/swnode.c:809
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
```
**Symbols:**

```
ffffffff81708610-ffffffff817086d7: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c2fe0)
Location: drivers/base/swnode.c:808
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
```
**Symbols:**

```
ffffffff817c2fe0-ffffffff817c30a6: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d7e20)
Location: drivers/base/swnode.c:811
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
```
**Symbols:**

```
ffffffff817d7e20-ffffffff817d7ee9: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bc140)
Location: drivers/base/swnode.c:979
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
  - drivers/base/swnode.c:device_create_managed_software_node
```
**Symbols:**

```
ffffffff817bc140-ffffffff817bc2b6: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81846430)
Location: drivers/base/swnode.c:981
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
  - drivers/base/swnode.c:device_create_managed_software_node
```
**Symbols:**

```
ffffffff81846430-ffffffff818465a6: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198a590)
Location: drivers/base/swnode.c:975
Inline: False
Direct callers:
  - drivers/base/swnode.c:device_create_managed_software_node
```
**Symbols:**

```
ffffffff8198a590-ffffffff8198a6f8: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81af99d0)
Location: drivers/base/swnode.c:975
Inline: False
Direct callers:
  - drivers/base/swnode.c:device_create_managed_software_node
```
**Symbols:**

```
ffffffff81af99d0-ffffffff81af9b38: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b47f80)
Location: drivers/base/swnode.c:914
Inline: False
Direct callers:
  - drivers/base/swnode.c:device_create_managed_software_node
```
**Symbols:**

```
ffffffff81b47f80-ffffffff81b480e8: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81ba0310)
Location: drivers/base/swnode.c:917
Inline: False
Direct callers:
  - drivers/base/swnode.c:device_create_managed_software_node
```
**Symbols:**

```
ffffffff81ba0310-ffffffff81ba04d6: fwnode_create_software_node (STB_GLOBAL)
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
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f6628)
Location: drivers/base/swnode.c:809
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
```
**Symbols:**

```
ffff8000108f6628-ffff8000108f6718: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e268c)
Location: drivers/base/swnode.c:809
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
```
**Symbols:**

```
c09e268c-c09e2760: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c000000000991910)
Location: drivers/base/swnode.c:809
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
```
**Symbols:**

```
c000000000991910-c000000000991a98: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe00058754c)
Location: drivers/base/swnode.c:809
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
```
**Symbols:**

```
ffffffe00058754c-ffffffe00058760e: fwnode_create_software_node (STB_GLOBAL)
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
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cdd60)
Location: drivers/base/swnode.c:809
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
```
**Symbols:**

```
ffffffff816cdd60-ffffffff816cde27: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a9090)
Location: drivers/base/swnode.c:809
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
```
**Symbols:**

```
ffffffff816a9090-ffffffff816a9157: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fc2d0)
Location: drivers/base/swnode.c:809
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
```
**Symbols:**

```
ffffffff816fc2d0-ffffffff816fc397: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_create_software_node(const struct property_entry *properties, const struct fwnode_handle *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81716e70)
Location: drivers/base/swnode.c:809
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
```
**Symbols:**

```
ffffffff81716e70-ffffffff81716f37: fwnode_create_software_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
